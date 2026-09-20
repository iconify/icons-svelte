<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o053b3bvz.css';
import '../../css/c/c06oizb4q.css';
import '../../css/m/m665vacsm.css';
import '../../css/k/km0xgebky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="o053b3bvz"/><path class="c06oizb4q"/><path class="m665vacsm"/><path class="km0xgebky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:calendar-clock" {...props}></Icon>
