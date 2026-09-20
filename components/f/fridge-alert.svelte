<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i1--_9dob.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i1--_9dob"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:fridge-alert" {...props}></Icon>
