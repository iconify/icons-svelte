<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s2rq36bvg.css';
import '../../css/s/s68-iubef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s2rq36bvg"/><path class="s68-iubef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:boolean-off-24" {...props}></Icon>
