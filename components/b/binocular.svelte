<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/k/kfk6dbcij.css';
import '../../css/t/thy5_2b8z.css';
import '../../css/y/ysc2kfs-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kfk6dbcij"/><path class="thy5_2b8z"/><path class="ysc2kfs-e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:binocular" {...props}></Icon>
