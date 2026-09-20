<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x2zr55bmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x2zr55bmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:book-open-outline" {...props}></Icon>
