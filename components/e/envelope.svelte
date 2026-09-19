<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jc9h1nboe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":750,"height":750};
const content = `<path class="jc9h1nboe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="il:envelope" {...props}></Icon>
