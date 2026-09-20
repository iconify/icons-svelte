<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vq29nsydq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="vq29nsydq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:celsius-remix" {...props}></Icon>
