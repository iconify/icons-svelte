<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tz00pjbrg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":718,"height":709};
const content = `<path class="tz00pjbrg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:magic" {...props}></Icon>
