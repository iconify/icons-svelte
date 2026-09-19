<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/txaa9ccku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="txaa9ccku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:bunny" {...props}></Icon>
