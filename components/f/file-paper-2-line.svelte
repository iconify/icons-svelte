<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/diuxkcx9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="diuxkcx9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:file-paper-2-line" {...props}></Icon>
