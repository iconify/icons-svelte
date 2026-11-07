<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ztyl-_j6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ztyl-_j6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:quantum-qpu" {...props}></Icon>
