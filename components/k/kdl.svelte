<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wqmi1bi_j.css';
import '../../css/i/i9il0nflb.css';
import '../../css/i/ijudkumzw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wqmi1bi_j"/><path class="i9il0nflb"/><path class="ijudkumzw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:kdl" {...props}></Icon>
