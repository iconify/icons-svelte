<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g6puw5bim.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g6puw5bim"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:question-mark-circle-outline" {...props}></Icon>
