<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xw_haib9d.css';
import '../../css/d/deidzy81h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xw_haib9d"/><path class="deidzy81h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:clippy-24" {...props}></Icon>
