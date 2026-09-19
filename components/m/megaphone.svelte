<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aacu17bhl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="aacu17bhl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:megaphone" {...props}></Icon>
