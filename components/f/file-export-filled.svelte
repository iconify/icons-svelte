<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a75vaqbtg.css';
import '../../css/m/m-ex0ftgv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a75vaqbtg"/><path class="m-ex0ftgv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:file-export-filled" {...props}></Icon>
