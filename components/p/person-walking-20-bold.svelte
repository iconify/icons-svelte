<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iu4y7jb0r.css';
import '../../css/e/etdcedcfw.css';
import '../../css/g/gg2u61y6d.css';
import '../../css/e/e88ivvz4f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="iu4y7jb0r"/><path class="etdcedcfw"/><path class="gg2u61y6d"/><path class="e88ivvz4f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:person-walking-20-bold" {...props}></Icon>
