<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_2e5hb8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r_2e5hb8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chevron-up-small-round" {...props}></Icon>
