<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fo81tgn7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fo81tgn7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:cloud-arrow-path" {...props}></Icon>
