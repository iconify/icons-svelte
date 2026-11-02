<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k6njk97az.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k6njk97az"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:progress-75-fill" {...props}></Icon>
