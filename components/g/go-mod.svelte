<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_fwht_fc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="b_fwht_fc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:go-mod" {...props}></Icon>
