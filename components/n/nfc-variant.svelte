<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f9x5jkb7j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f9x5jkb7j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:nfc-variant" {...props}></Icon>
