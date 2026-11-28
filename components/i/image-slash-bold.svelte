<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ku9l-5byw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="ku9l-5byw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:image-slash-bold" {...props}></Icon>
