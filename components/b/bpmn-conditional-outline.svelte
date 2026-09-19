<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fdb5gbc-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fdb5gbc-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:bpmn-conditional-outline" {...props}></Icon>
