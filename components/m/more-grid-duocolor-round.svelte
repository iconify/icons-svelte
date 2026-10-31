<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/in7g9uh7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="in7g9uh7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:more-grid-duocolor-round" {...props}></Icon>
