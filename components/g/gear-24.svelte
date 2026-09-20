<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q6wgzy02y.css';
import '../../css/r/rhjnb0hvn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q6wgzy02y"/><path class="rhjnb0hvn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:gear-24" {...props}></Icon>
