<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a5axhacgi.css';
import '../../css/l/lmu4qk5wf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="a5axhacgi"/><path clip-rule="evenodd" class="lmu4qk5wf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:faq-16" {...props}></Icon>
