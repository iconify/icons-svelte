<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-zwmgb6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="q-zwmgb6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="quill:calendar" {...props}></Icon>
