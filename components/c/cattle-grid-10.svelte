<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g30n8ubuk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":10,"height":10};
const content = `<path class="g30n8ubuk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:cattle-grid-10" {...props}></Icon>
