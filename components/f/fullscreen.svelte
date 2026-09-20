<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/banpgub-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="banpgub-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:fullscreen" {...props}></Icon>
