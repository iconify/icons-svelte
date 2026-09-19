<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i0ar89bxd.css';
import '../../css/c/c7hrc7bds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="i0ar89bxd"/><path class="c7hrc7bds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:previous-filled" {...props}></Icon>
