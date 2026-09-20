<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m4e1w5h4h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m4e1w5h4h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:building-pavilion" {...props}></Icon>
