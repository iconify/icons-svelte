<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/di1mk4dfd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="di1mk4dfd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:equals-20-solid" {...props}></Icon>
