<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wo3chwbhv.css';
import '../../css/c/co_00rbvb.css';
import '../../css/u/uwt2fqejw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="wo3chwbhv"/><path class="co_00rbvb"/><path class="uwt2fqejw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:charging-cable-20-bold" {...props}></Icon>
