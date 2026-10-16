<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/agoxzxbge.css';
import '../../css/m/mb2ru1gou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="agoxzxbge"/><path class="mb2ru1gou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chain-20-bold" {...props}></Icon>
