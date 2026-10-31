<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kpgnsfbyn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kpgnsfbyn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:pinterest-round" {...props}></Icon>
