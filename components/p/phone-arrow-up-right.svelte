<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ffdwxrmjl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ffdwxrmjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:phone-arrow-up-right" {...props}></Icon>
