<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n9ze8629c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":496,"height":512};
const content = `<path class="n9ze8629c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:radiation" {...props}></Icon>
