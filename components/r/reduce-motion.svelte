<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8n2ao-nj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n8n2ao-nj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:reduce-motion" {...props}></Icon>
