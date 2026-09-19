<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kpcyqvbjj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kpcyqvbjj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:drink-me" {...props}></Icon>
