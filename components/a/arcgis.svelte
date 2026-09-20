<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vowv2jbsn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vowv2jbsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:arcgis" {...props}></Icon>
