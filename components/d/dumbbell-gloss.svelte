<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wpf005l-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wpf005l-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:dumbbell-gloss" {...props}></Icon>
