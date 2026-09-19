<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ltp815bff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="ltp815bff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:docker" {...props}></Icon>
