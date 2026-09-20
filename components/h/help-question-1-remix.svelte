<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kci8ccoim.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="kci8ccoim"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:help-question-1-remix" {...props}></Icon>
