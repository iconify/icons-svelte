<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b1_805bdn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="b1_805bdn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:neuter-solid" {...props}></Icon>
