<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j3emfubau.css';
import '../../css/a/ai0csy1rf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="j3emfubau"/><path class="ai0csy1rf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:edit-48" {...props}></Icon>
