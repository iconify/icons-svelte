<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fftc1hb4y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fftc1hb4y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:app-window-cursor-sharp-fill" {...props}></Icon>
