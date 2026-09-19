<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ky2xp9bva.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ky2xp9bva"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:gup" {...props}></Icon>
