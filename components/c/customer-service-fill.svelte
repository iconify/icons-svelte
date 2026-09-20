<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/io8fdue6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="io8fdue6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:customer-service-fill" {...props}></Icon>
