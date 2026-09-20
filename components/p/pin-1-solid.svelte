<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/avgb43z_v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="avgb43z_v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:pin-1-solid" {...props}></Icon>
