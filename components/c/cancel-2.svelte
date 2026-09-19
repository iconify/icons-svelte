<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kcuhc8bwo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="kcuhc8bwo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:cancel-2" {...props}></Icon>
