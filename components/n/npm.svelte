<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ootz-9bss.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ootz-9bss"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:npm" {...props}></Icon>
