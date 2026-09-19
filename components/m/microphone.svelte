<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bac56-jdz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1152,"height":1664};
const content = `<path class="bac56-jdz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:microphone" {...props}></Icon>
