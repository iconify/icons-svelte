<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/anvn59byi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="anvn59byi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:barcode" {...props}></Icon>
