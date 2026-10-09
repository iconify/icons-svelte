<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hseox7a5f.css';
import '../../css/r/rdbz-ccxi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hseox7a5f"/><path class="rdbz-ccxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:countryside-20-bold" {...props}></Icon>
