<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wvggjxpqo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wvggjxpqo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:bill-4-remix" {...props}></Icon>
