<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fo08aslyx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fo08aslyx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:facebook-logo-2-block" {...props}></Icon>
