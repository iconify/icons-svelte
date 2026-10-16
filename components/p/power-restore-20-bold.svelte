<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hs3_9lslw.css';
import '../../css/j/jg-yaccaq.css';
import '../../css/e/exrx6ubga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hs3_9lslw"/><path class="jg-yaccaq"/><path class="exrx6ubga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:power-restore-20-bold" {...props}></Icon>
