<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ev0k3vk4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":63,"height":64};
const content = `<path class="ev0k3vk4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:first-aid" {...props}></Icon>
