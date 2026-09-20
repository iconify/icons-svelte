<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vc5lsvbrb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vc5lsvbrb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:dice-d10" {...props}></Icon>
