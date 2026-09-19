<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qbu_57tmg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qbu_57tmg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:hell-crosses" {...props}></Icon>
