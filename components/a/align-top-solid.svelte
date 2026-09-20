<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-cdjgbrd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="q-cdjgbrd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:align-top-solid" {...props}></Icon>
