<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i82rs5bju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i82rs5bju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:more-vertical-duocolor-round" {...props}></Icon>
