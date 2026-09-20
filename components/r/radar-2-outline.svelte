<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h0j_14bol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h0j_14bol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:radar-2-outline" {...props}></Icon>
