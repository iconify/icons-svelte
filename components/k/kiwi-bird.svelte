<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tiox78u5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="tiox78u5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:kiwi-bird" {...props}></Icon>
