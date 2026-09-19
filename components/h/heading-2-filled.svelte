<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e6hcv8b7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e6hcv8b7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:heading-2-filled" {...props}></Icon>
