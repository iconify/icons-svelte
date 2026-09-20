<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o794mi5kt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o794mi5kt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:file-filled" {...props}></Icon>
