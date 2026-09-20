<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kgxw63bss.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="kgxw63bss"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:first-order" {...props}></Icon>
