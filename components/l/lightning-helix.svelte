<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-wuzzo5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a-wuzzo5c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:lightning-helix" {...props}></Icon>
