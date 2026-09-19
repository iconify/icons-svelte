<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wo4vm5lrz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wo4vm5lrz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:document-upload" {...props}></Icon>
