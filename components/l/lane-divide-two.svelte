<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iwi8gpbuh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="iwi8gpbuh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bpmn:lane-divide-two" {...props}></Icon>
