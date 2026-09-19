<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h-3v2hqse.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="h-3v2hqse"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:arrow-uturn-up" {...props}></Icon>
