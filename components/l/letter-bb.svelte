<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uph1ozkms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="uph1ozkms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:letter-bb" {...props}></Icon>
