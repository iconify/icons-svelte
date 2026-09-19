<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ejl9ky0qb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ejl9ky0qb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:notification-off" {...props}></Icon>
