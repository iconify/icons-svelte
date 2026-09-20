<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/isq7whgdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="isq7whgdi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:progress" {...props}></Icon>
