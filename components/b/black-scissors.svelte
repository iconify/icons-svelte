<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/od9c0scqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="od9c0scqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:black-scissors" {...props}></Icon>
