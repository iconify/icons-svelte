<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lk8ejyb7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lk8ejyb7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:cloud" {...props}></Icon>
