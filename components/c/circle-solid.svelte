<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mo0c_kb7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<circle class="mo0c_kb7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:circle-solid" {...props}></Icon>
