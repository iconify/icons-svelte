<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b2bh_xjbn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b2bh_xjbn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:mighty-horn" {...props}></Icon>
