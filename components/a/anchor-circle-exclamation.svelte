<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d8ssn3b7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="d8ssn3b7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:anchor-circle-exclamation" {...props}></Icon>
