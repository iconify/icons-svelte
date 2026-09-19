<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qfttfe_2y.css';
import '../../css/j/jc7bipbfp.css';
import '../../css/r/rc5rj3blu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="qfttfe_2y"><path class="jc7bipbfp"/><path class="rc5rj3blu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:cuda" {...props}></Icon>
