<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wlyd17xxc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wlyd17xxc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:margin-left" {...props}></Icon>
