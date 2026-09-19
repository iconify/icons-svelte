<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xz6yknbnq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="xz6yknbnq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:currency-euro-16-solid" {...props}></Icon>
