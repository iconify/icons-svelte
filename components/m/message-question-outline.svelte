<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fu7_340-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fu7_340-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:message-question-outline" {...props}></Icon>
