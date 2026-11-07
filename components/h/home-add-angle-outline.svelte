<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fipmm04et.css';
import '../../css/w/wru8zmbec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fipmm04et"/><path clip-rule="evenodd" class="wru8zmbec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:home-add-angle-outline" {...props}></Icon>
