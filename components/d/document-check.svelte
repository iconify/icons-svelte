<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x12oh9b_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x12oh9b_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:document-check" {...props}></Icon>
