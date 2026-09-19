<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bv1hz3b5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="bv1hz3b5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:nuxt-ignore" {...props}></Icon>
