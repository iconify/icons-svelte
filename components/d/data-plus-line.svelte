<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aesn7b_0u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aesn7b_0u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:data-plus-line" {...props}></Icon>
