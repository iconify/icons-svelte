<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nq76hyvxq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nq76hyvxq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:new-sticky-note-solid" {...props}></Icon>
