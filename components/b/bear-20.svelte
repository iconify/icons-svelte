<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/suuvhacgc.css';
import '../../css/c/codq7jbgp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="suuvhacgc"/><path class="codq7jbgp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bear-20" {...props}></Icon>
