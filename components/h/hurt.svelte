<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zbssn3qev.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zbssn3qev"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:hurt" {...props}></Icon>
