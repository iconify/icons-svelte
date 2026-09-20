<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/evu18mh8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="evu18mh8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:file-pdf-line" {...props}></Icon>
