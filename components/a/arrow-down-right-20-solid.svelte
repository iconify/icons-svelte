<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/juh-xlr9r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="juh-xlr9r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-down-right-20-solid" {...props}></Icon>
