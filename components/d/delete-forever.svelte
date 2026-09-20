<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tebu7d1rx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tebu7d1rx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:delete-forever" {...props}></Icon>
