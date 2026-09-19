<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/crub4ucgs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="crub4ucgs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:minus-outline" {...props}></Icon>
