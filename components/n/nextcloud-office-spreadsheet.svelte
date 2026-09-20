<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z13q2gbji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z13q2gbji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nextcloud-office-spreadsheet" {...props}></Icon>
