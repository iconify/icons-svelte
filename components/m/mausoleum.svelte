<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sdn95mbqv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="sdn95mbqv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:mausoleum" {...props}></Icon>
