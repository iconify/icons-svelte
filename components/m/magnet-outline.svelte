<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u37-xachj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u37-xachj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:magnet-outline" {...props}></Icon>
