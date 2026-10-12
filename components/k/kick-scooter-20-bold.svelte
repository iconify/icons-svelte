<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c9astq9iv.css';
import '../../css/t/ts6ghieqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="c9astq9iv"/><path class="ts6ghieqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:kick-scooter-20-bold" {...props}></Icon>
