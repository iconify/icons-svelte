<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/npwtzq6gi.css';
import '../../css/u/uq5sy7bwp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="npwtzq6gi"/><path class="uq5sy7bwp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:oven-20-bold" {...props}></Icon>
