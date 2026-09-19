<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hwr6088ru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="hwr6088ru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-regular:money-bill-1" {...props}></Icon>
