<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p6mhhybdk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":65,"height":64};
const content = `<path class="p6mhhybdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:health-education" {...props}></Icon>
