<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w9b1o0b9t.css';
import '../../css/m/mcwbb7b7p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<circle class="w9b1o0b9t"/><path class="mcwbb7b7p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:instance-virtual" {...props}></Icon>
