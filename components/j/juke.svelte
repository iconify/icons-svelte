<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-_s3dl-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x-_s3dl-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:juke" {...props}></Icon>
