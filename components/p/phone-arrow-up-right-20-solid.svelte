<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p0dm81bww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="p0dm81bww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:phone-arrow-up-right-20-solid" {...props}></Icon>
