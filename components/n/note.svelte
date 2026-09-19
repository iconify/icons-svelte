<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cwysebc2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="cwysebc2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:note" {...props}></Icon>
