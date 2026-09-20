<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lg4mb7p2r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lg4mb7p2r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:colour-tuning-outline" {...props}></Icon>
