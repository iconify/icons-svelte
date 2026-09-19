<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bh4utmb2f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bh4utmb2f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:american-shield" {...props}></Icon>
