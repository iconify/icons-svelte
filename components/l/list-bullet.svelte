<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hu1ta9w8f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="hu1ta9w8f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:list-bullet" {...props}></Icon>
