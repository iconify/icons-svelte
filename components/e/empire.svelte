<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m6-xaeb1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="m6-xaeb1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:empire" {...props}></Icon>
