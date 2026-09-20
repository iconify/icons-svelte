<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ei8_h1b7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ei8_h1b7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:play-previous-line" {...props}></Icon>
