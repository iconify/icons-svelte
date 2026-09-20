<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ov5ht6eqo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ov5ht6eqo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:palete" {...props}></Icon>
