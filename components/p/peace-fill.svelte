<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z0s_31-tx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="z0s_31-tx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:peace-fill" {...props}></Icon>
