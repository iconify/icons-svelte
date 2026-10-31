<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uddg1p2yu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uddg1p2yu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:indent" {...props}></Icon>
