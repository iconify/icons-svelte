<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wet0bllvk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="wet0bllvk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:otp-outline" {...props}></Icon>
