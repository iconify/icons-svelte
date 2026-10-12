<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tf1d1ooga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tf1d1ooga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:align-vertical-justify-center-filled" {...props}></Icon>
