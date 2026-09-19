<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sq89r7b6w.css';
import '../../css/x/x_8ggbcrp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<circle class="sq89r7b6w"/><path class="x_8ggbcrp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:question-mark-fill-16" {...props}></Icon>
