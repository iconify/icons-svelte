<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v8jg2bc8j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v8jg2bc8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:currency-dollar-duotone-round" {...props}></Icon>
