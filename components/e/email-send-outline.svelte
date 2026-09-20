<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/af8j95bax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="af8j95bax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:email-send-outline" {...props}></Icon>
