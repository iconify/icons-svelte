<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gs8t_dbid.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gs8t_dbid"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:floppy-disc-edit-outline" {...props}></Icon>
