<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f4_i3vb-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1800,"height":1800};
const content = `<path class="f4_i3vb-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:resend-dark" {...props}></Icon>
