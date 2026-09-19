<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c274zs7rb.css';
import '../../css/m/mwlmtkbnp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="c274zs7rb"/><path class="mwlmtkbnp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:football" {...props}></Icon>
