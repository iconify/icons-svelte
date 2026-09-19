<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x5luqjpur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x5luqjpur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:inbox" {...props}></Icon>
