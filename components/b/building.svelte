<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zpwaw1qia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="zpwaw1qia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:building" {...props}></Icon>
