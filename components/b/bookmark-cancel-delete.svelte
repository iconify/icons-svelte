<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q--benb2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q--benb2w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:bookmark-cancel-delete" {...props}></Icon>
