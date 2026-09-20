<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r9w7oc8rl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r9w7oc8rl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:homarr" {...props}></Icon>
