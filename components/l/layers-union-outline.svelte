<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fhtq3obqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="fhtq3obqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:layers-union-outline" {...props}></Icon>
