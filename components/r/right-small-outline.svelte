<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fr6y515mv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="fr6y515mv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:right-small-outline" {...props}></Icon>
