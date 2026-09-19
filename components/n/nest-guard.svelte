<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wjnyjob-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wjnyjob-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:nest-guard" {...props}></Icon>
