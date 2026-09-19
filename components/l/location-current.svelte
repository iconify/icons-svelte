<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/esl1noc6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="esl1noc6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:location-current" {...props}></Icon>
