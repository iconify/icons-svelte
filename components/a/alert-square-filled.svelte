<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ep8q4pb1g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ep8q4pb1g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:alert-square-filled" {...props}></Icon>
