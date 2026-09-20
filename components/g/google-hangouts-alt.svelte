<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nw4_fx-en.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nw4_fx-en"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:google-hangouts-alt" {...props}></Icon>
