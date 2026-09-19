<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ztw00-h6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="ztw00-h6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:first-aid-kit-solid" {...props}></Icon>
