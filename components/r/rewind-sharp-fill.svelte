<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ja0gh3bfi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ja0gh3bfi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:rewind-sharp-fill" {...props}></Icon>
