<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rh_luwtku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="rh_luwtku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:qt" {...props}></Icon>
