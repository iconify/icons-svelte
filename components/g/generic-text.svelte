<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oov311bqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="oov311bqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:generic-text" {...props}></Icon>
