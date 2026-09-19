<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jjrh6jb6e.css';
import '../../css/q/qpqtl2biq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="jjrh6jb6e"/><path class="qpqtl2biq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:kaldi-wordmark" {...props}></Icon>
