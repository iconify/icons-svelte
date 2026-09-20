<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fpby05bnb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fpby05bnb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:megaphone" {...props}></Icon>
