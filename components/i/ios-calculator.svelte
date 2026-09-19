<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-2occ2bb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p-2occ2bb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-calculator" {...props}></Icon>
