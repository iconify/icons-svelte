<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dd66-6xai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dd66-6xai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:orc-head" {...props}></Icon>
