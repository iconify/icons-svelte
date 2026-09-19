<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zjn-iubyv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zjn-iubyv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:fez" {...props}></Icon>
