<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fn0lll37g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fn0lll37g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:pear" {...props}></Icon>
