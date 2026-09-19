<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eebg1actu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="eebg1actu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:pin-3" {...props}></Icon>
