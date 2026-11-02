<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sjqd8mbll.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sjqd8mbll"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:circle-divide-fill" {...props}></Icon>
