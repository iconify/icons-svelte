<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bbp5c087e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="bbp5c087e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:id-card" {...props}></Icon>
