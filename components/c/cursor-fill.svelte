<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bklllhg4u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="bklllhg4u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:cursor-fill" {...props}></Icon>
