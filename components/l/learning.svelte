<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/s/sd5pw-b8u.css';
import '../../css/m/mitl-8btu.css';
import '../../css/p/pod1yswni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sd5pw-b8u"/><path class="mitl-8btu"/><path class="pod1yswni"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:learning" {...props}></Icon>
