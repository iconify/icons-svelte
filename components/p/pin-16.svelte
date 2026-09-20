<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bw1ug-btp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="bw1ug-btp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:pin-16" {...props}></Icon>
