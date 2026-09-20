<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/a/a9bub1fqj.css';
import '../../css/q/qsokfzbll.css';
import '../../css/f/fbsjc3a0u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><rect class="a9bub1fqj"/><circle class="qsokfzbll"/><path class="fbsjc3a0u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:camera-2" {...props}></Icon>
