<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-vp4jbjl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y-vp4jbjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:file-pdf-24" {...props}></Icon>
