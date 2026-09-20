<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r---78b9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="r---78b9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:android-outline" {...props}></Icon>
