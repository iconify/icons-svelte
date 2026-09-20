<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fr4pidc2z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="fr4pidc2z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:flat-head-thumb-tack" {...props}></Icon>
