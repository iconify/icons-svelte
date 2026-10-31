<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x1b9j_3vc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x1b9j_3vc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:arrow-up-right-large-fill-round" {...props}></Icon>
