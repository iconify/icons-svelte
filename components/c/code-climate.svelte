<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a6nnlgbfv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":300,"height":300};
const content = `<path class="a6nnlgbfv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:code-climate" {...props}></Icon>
