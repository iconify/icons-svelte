<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u98q4jbst.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":960,"height":960};
const content = `<path class="u98q4jbst"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:innerborders" {...props}></Icon>
