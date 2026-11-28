<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ilfdkkb1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ilfdkkb1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:inbox-check" {...props}></Icon>
