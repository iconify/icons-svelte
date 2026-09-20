<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j8bqi5ahx.css';
import '../../css/c/cq-wbst_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="j8bqi5ahx"/><path class="cq-wbst_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:eye-slash" {...props}></Icon>
