<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t01b7nbne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="t01b7nbne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bpmn:lane-divide-three" {...props}></Icon>
