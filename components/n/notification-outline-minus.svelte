<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mltf9q9oz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mltf9q9oz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:notification-outline-minus" {...props}></Icon>
