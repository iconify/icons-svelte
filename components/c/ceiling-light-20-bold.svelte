<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fo_phgozt.css';
import '../../css/c/c7-acjc4q.css';
import '../../css/n/n2-k-0btv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fo_phgozt"/><path class="c7-acjc4q"/><path class="n2-k-0btv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ceiling-light-20-bold" {...props}></Icon>
