<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mjfga9bzu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mjfga9bzu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:cloud-download-round" {...props}></Icon>
