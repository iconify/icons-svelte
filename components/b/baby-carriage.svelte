<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u-k_aebkz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u-k_aebkz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:baby-carriage" {...props}></Icon>
