<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ehgdjcc8o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="ehgdjcc8o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:fork" {...props}></Icon>
