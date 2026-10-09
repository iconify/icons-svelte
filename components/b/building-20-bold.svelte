<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t9ufisb4k.css';
import '../../css/t/t3wwm-c_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="t9ufisb4k"/><path class="t3wwm-c_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:building-20-bold" {...props}></Icon>
