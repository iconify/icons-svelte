<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lef9jzxzs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lef9jzxzs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:no-ticket" {...props}></Icon>
