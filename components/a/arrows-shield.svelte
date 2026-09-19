<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ok8n22bvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ok8n22bvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:arrows-shield" {...props}></Icon>
