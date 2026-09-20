<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/emvguebok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="emvguebok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:beer-glass-bold" {...props}></Icon>
