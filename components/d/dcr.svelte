<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t5-xncc3n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="t5-xncc3n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:dcr" {...props}></Icon>
