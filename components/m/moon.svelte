<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w9r5umzcg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w9r5umzcg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:moon" {...props}></Icon>
