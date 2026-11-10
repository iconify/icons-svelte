<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qdfu3-prn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qdfu3-prn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:cloud-exclamation" {...props}></Icon>
