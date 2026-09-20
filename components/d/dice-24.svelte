<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s2rq36bvg.css';
import '../../css/m/mzvqb-b0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s2rq36bvg"/><path class="mzvqb-b0r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:dice-24" {...props}></Icon>
