<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z7tmoxkid.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z7tmoxkid"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:handbag-fill-round" {...props}></Icon>
