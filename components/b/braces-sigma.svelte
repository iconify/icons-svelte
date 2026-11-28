<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/crf7kdxjj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="crf7kdxjj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:braces-sigma" {...props}></Icon>
