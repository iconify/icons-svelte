<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kmj6onr3b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="kmj6onr3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:diagram-2" {...props}></Icon>
