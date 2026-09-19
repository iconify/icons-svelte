<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x_3m48bsi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x_3m48bsi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:bitty-filled" {...props}></Icon>
