<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jg3gzprxi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jg3gzprxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:file-table-box-multiple" {...props}></Icon>
