<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wegkaw1iq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wegkaw1iq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:comment-fill" {...props}></Icon>
