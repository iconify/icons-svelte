<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yneuenbae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yneuenbae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:phone-off-filled" {...props}></Icon>
