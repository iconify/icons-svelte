<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nhie0db7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nhie0db7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:qnap" {...props}></Icon>
