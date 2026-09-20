<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tnmrr0r5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="tnmrr0r5c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:eye" {...props}></Icon>
