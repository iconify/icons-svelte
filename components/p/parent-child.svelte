<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g7xogobtu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="g7xogobtu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:parent-child" {...props}></Icon>
