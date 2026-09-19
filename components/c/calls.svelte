<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ex9iwebhk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ex9iwebhk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:calls" {...props}></Icon>
