<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n87f4mb-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":850};
const content = `<path class="n87f4mb-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="il:paypal" {...props}></Icon>
