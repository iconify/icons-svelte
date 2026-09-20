<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h83zg0bkr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="h83zg0bkr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:media-step-backward" {...props}></Icon>
