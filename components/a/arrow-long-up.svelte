<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a92qnq0-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="a92qnq0-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:arrow-long-up" {...props}></Icon>
