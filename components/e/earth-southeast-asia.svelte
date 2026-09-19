<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b78-uobgs.css';
import '../../css/e/eqms1ckur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="b78-uobgs"/><path class="eqms1ckur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:earth-southeast-asia" {...props}></Icon>
