<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ftw-gh2gl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ftw-gh2gl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="feather:phone-forwarded" {...props}></Icon>
