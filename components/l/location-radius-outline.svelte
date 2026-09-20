<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/orkur467v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="orkur467v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:location-radius-outline" {...props}></Icon>
