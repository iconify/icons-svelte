<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/erq5l0bdy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":300,"height":300};
const content = `<path class="erq5l0bdy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:flow" {...props}></Icon>
