<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wkuowk5pf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wkuowk5pf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:inverted-dice-3" {...props}></Icon>
