<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ogsukvk9r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ogsukvk9r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:arrow-big-up-bulk-round" {...props}></Icon>
