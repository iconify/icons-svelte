<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/g/g7e2eab1a.css';
import '../../css/u/u-2m9hbse.css';
import '../../css/v/vmccjbb6s.css';
import '../../css/a/a3scpvo1f.css';
import '../../css/e/eck4ylbag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="g7e2eab1a"/><path class="u-2m9hbse"/><path class="vmccjbb6s"/><path class="a3scpvo1f"/><path class="eck4ylbag"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:hand-stars-linear" {...props}></Icon>
