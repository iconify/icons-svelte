<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/odjw9lbqc.css';
import '../../css/n/nn95hacfk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="odjw9lbqc"/><path class="nn95hacfk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:records" {...props}></Icon>
