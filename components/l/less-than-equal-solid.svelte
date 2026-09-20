<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ezp0t7b4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ezp0t7b4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:less-than-equal-solid" {...props}></Icon>
