<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cdorq249g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cdorq249g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:file-text-multiple" {...props}></Icon>
