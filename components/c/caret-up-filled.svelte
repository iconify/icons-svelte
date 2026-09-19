<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f8p_cp7cv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f8p_cp7cv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:caret-up-filled" {...props}></Icon>
