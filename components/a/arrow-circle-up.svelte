<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/esny0jbie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="esny0jbie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:arrow-circle-up" {...props}></Icon>
