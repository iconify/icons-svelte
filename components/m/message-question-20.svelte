<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fzs5177np.css';
import '../../css/n/non1cd9gr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fzs5177np"/><path class="non1cd9gr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:message-question-20" {...props}></Icon>
