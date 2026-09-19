<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sgms884ft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="sgms884ft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:bpmn-link-fill" {...props}></Icon>
