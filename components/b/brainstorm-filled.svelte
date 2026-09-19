<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jfseippgt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jfseippgt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:brainstorm-filled" {...props}></Icon>
