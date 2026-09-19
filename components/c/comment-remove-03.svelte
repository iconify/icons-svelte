<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k0ooocc1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k0ooocc1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:comment-remove-03" {...props}></Icon>
