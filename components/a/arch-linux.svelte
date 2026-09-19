<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o0f7r1b9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="o0f7r1b9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:arch-linux" {...props}></Icon>
