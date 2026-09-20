<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jugeylblu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jugeylblu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:mx-linux-logo" {...props}></Icon>
