<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mwmdc8b7j.css';
import '../../css/y/y5nzee3jx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mwmdc8b7j"/><path class="y5nzee3jx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:file-zip" {...props}></Icon>
