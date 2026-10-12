<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/po9ungb1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="po9ungb1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:logo-facebook-20" {...props}></Icon>
