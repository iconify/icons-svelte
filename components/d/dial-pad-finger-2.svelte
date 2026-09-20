<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ro4w9ibtr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ro4w9ibtr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:dial-pad-finger-2" {...props}></Icon>
