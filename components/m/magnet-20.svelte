<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kvc1jlbnu.css';
import '../../css/j/juittjbbz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="kvc1jlbnu"/><path class="juittjbbz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:magnet-20" {...props}></Icon>
