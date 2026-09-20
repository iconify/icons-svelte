<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-3zwldxa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o-3zwldxa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:customer-service-line" {...props}></Icon>
