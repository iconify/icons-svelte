<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kimfu9q5t.css';
import '../../css/o/ow_xmxbad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="kimfu9q5t"/><path class="ow_xmxbad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:file-question-20" {...props}></Icon>
