<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/arebbvaap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1408};
const content = `<path class="arebbvaap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:align-left" {...props}></Icon>
