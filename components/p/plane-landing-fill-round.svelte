<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/faf-8419w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="faf-8419w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:plane-landing-fill-round" {...props}></Icon>
