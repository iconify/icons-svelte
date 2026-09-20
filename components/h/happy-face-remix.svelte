<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/np5g_yzxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="np5g_yzxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:happy-face-remix" {...props}></Icon>
