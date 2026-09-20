<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q9x6-5j_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="q9x6-5j_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:basic-ui-question-2" {...props}></Icon>
