<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lk7y6rbwz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lk7y6rbwz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:list-20-bold" {...props}></Icon>
