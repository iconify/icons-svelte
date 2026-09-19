<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c8a1lb6mn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c8a1lb6mn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:copy-fill" {...props}></Icon>
