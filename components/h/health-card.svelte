<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cqe-vxb7s.css';
import '../../css/f/f_uwr3bjt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="cqe-vxb7s"/><path class="f_uwr3bjt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:health-card" {...props}></Icon>
