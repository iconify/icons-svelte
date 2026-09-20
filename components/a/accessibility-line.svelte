<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sdwqgyboe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sdwqgyboe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:accessibility-line" {...props}></Icon>
