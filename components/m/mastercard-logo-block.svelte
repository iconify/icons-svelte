<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f36i_688s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f36i_688s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:mastercard-logo-block" {...props}></Icon>
