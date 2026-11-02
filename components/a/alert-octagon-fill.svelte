<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oee8e_b-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oee8e_b-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:alert-octagon-fill" {...props}></Icon>
