<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oiff-v72c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="oiff-v72c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:odnoklassniki-square" {...props}></Icon>
