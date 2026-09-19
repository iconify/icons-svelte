<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gfvo-obul.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gfvo-obul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:arrow-back-sharp" {...props}></Icon>
