<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oplgkni-q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oplgkni-q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:file-remove-outline" {...props}></Icon>
