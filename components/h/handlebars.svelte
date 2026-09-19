<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aazry6bnq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="aazry6bnq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:handlebars" {...props}></Icon>
