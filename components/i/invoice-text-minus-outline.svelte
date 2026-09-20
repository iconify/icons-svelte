<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h5qo3wbtj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h5qo3wbtj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:invoice-text-minus-outline" {...props}></Icon>
