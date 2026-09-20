<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fu5eqibwv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fu5eqibwv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:bbc-iplayer-logo-2-block" {...props}></Icon>
