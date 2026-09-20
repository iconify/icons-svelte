<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xz_intbaq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xz_intbaq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:kanban-solid" {...props}></Icon>
