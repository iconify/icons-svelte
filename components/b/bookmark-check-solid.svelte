<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nqa7h_o0d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nqa7h_o0d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:bookmark-check-solid" {...props}></Icon>
