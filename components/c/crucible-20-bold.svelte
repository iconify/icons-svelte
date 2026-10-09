<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fclurev-p.css';
import '../../css/v/v-lkcnbeq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fclurev-p"/><path class="v-lkcnbeq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:crucible-20-bold" {...props}></Icon>
