<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tdx7i4plj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tdx7i4plj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:megaphone" {...props}></Icon>
