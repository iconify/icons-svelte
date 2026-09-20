<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v63eijmiu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="v63eijmiu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:clapperboard" {...props}></Icon>
