<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ijwutn8tg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ijwutn8tg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:rotating-forward" {...props}></Icon>
