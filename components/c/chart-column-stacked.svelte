<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rzh6r_7vk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rzh6r_7vk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:chart-column-stacked" {...props}></Icon>
