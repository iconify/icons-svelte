<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i188si0ua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="i188si0ua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:queue-list" {...props}></Icon>
