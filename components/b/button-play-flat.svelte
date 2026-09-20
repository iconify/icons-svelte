<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-izh3bji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="q-izh3bji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:button-play-flat" {...props}></Icon>
