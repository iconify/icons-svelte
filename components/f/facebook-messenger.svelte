<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fckdgqt-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fckdgqt-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:facebook-messenger" {...props}></Icon>
