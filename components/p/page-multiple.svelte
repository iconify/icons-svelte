<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/run4fcbjt.css';
import '../../css/y/y_7gziaml.css';
import '../../css/f/fzp0gcbsh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="run4fcbjt"/><path class="y_7gziaml"/><path class="fzp0gcbsh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:page-multiple" {...props}></Icon>
