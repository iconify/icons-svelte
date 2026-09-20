<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w-v8y7ptm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="w-v8y7ptm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:lock-open" {...props}></Icon>
