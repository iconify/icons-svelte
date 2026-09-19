<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oc1enib9k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<circle class="oc1enib9k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:dot-mark" {...props}></Icon>
