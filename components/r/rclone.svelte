<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xh37ilbjo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xh37ilbjo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:rclone" {...props}></Icon>
