<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uzh21_idx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uzh21_idx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-cyber:piano-1" {...props}></Icon>
