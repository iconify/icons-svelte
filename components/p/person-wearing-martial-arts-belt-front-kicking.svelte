<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aih13zb3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="aih13zb3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-wearing-martial-arts-belt-front-kicking" {...props}></Icon>
