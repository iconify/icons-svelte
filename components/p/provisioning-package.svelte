<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ikgv0kb3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="ikgv0kb3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:provisioning-package" {...props}></Icon>
