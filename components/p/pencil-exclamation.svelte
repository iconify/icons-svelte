<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mc8hf49pm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mc8hf49pm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:pencil-exclamation" {...props}></Icon>
