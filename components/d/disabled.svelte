<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kdhhz2seu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":496,"height":512};
const content = `<path class="kdhhz2seu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:disabled" {...props}></Icon>
