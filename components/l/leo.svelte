<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bh3nvab7f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bh3nvab7f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:leo" {...props}></Icon>
