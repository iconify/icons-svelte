<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lhuk8-b5y.css';
import '../../css/u/u8bmg4bmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lhuk8-b5y"/><path class="u8bmg4bmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:deforestation-20-bold" {...props}></Icon>
