<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nkxip9b3n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nkxip9b3n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:arrow-up-right-round" {...props}></Icon>
