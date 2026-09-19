<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x9t5qgbnj.css';
import '../../css/u/uqsh6ibhf.css';
import '../../css/p/pr87757ke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="x9t5qgbnj"/><path class="uqsh6ibhf"/><circle class="pr87757ke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:lock" {...props}></Icon>
