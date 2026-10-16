<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uw-oesbrl.css';
import '../../css/n/nuvmf9bii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="uw-oesbrl"/><path class="nuvmf9bii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:battery-pouch-20-bold" {...props}></Icon>
