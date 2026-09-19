<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fklqo_fws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="fklqo_fws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:flag-finish" {...props}></Icon>
