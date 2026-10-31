<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q8j3v-iti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q8j3v-iti"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:avatar-fox-gloss" {...props}></Icon>
