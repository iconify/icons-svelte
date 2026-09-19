<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v8ojk_b7y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="v8ojk_b7y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:bpmn-link-outline" {...props}></Icon>
