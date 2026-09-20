<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d9s7qk7ci.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="d9s7qk7ci"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:pin" {...props}></Icon>
