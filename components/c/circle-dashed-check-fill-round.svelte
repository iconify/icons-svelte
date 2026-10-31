<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u_9fq3bnd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u_9fq3bnd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:circle-dashed-check-fill-round" {...props}></Icon>
