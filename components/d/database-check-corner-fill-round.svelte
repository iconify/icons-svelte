<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/joq9umt7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="joq9umt7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:database-check-corner-fill-round" {...props}></Icon>
