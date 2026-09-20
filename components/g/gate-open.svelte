<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a5smqebaa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a5smqebaa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:gate-open" {...props}></Icon>
