<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ez22xh-gg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ez22xh-gg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:child-20" {...props}></Icon>
