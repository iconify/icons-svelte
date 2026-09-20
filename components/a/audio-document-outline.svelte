<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hig8vmu5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="hig8vmu5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:audio-document-outline" {...props}></Icon>
