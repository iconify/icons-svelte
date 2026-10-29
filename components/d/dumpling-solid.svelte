<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n9__an07j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n9__an07j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:dumpling-solid" {...props}></Icon>
