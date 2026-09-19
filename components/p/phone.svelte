<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n9hia6hcn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n9hia6hcn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:phone" {...props}></Icon>
