<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tc2pc3bcw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1800,"height":1800};
const content = `<path class="tc2pc3bcw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:resend-light" {...props}></Icon>
