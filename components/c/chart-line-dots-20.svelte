<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/km2fl-ght.css';
import '../../css/n/nhk0vvrvh.css';
import '../../css/s/s39uf-bmg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="km2fl-ght"/><path class="nhk0vvrvh"/><path class="s39uf-bmg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chart-line-dots-20" {...props}></Icon>
