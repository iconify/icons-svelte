<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hvzbo5e7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hvzbo5e7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:basketball" {...props}></Icon>
