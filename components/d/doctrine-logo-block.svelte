<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i3-w3f3uo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i3-w3f3uo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:doctrine-logo-block" {...props}></Icon>
