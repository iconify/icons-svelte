<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bxamrnbvx.css';
import '../../css/t/tiebub9tw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bxamrnbvx"/><path class="tiebub9tw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-plus-outline" {...props}></Icon>
