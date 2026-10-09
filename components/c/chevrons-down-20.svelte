<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/deisahb9j.css';
import '../../css/b/bfngflyuv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="deisahb9j"/><path class="bfngflyuv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chevrons-down-20" {...props}></Icon>
