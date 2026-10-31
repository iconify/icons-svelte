<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ymnavtb7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ymnavtb7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:arrow-up-large-bulk-round" {...props}></Icon>
