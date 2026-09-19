<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ixmy2_bju.css';
import '../../css/a/al6kmgb1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ixmy2_bju"/><path class="al6kmgb1k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:nx-ignore" {...props}></Icon>
