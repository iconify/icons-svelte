<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e3jwm-izx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e3jwm-izx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:currency-euro-fill-round" {...props}></Icon>
