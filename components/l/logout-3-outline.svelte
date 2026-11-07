<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wq2w7o_df.css';
import '../../css/i/i742icc9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wq2w7o_df"/><path clip-rule="evenodd" class="i742icc9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:logout-3-outline" {...props}></Icon>
