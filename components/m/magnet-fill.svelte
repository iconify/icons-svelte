<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m2n_u8yaa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="m2n_u8yaa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:magnet-fill" {...props}></Icon>
