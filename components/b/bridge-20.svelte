<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1t5mtm0a.css';
import '../../css/w/w1gklacoq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="n1t5mtm0a"/><path class="w1gklacoq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bridge-20" {...props}></Icon>
