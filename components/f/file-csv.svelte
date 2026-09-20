<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gmzbb3bza.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gmzbb3bza"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:file-csv" {...props}></Icon>
