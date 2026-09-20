<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r095fdb0a.css';
import '../../css/s/sgkeqm1ah.css';
import '../../css/r/ruj0ehbjh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="r095fdb0a"/><path class="sgkeqm1ah"/><path class="ruj0ehbjh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:copy" {...props}></Icon>
