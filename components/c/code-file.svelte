<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tt2awjbju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="tt2awjbju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:code-file" {...props}></Icon>
