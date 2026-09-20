<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-h60obbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":25};
const content = `<path class="y-h60obbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:arrow-angular-top-left" {...props}></Icon>
