<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cczy4x2em.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="cczy4x2em"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:cloud-lightning-rain" {...props}></Icon>
