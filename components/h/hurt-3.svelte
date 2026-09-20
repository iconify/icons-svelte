<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b7goi0bav.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b7goi0bav"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:hurt-3" {...props}></Icon>
