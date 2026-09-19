<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rh_exqb_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rh_exqb_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-email-outline" {...props}></Icon>
