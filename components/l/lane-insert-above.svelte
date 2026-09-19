<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v-y0q6rwd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="v-y0q6rwd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bpmn:lane-insert-above" {...props}></Icon>
