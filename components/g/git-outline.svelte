<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/trotqwbxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="trotqwbxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:git-outline" {...props}></Icon>
