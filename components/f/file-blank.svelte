<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ofcnx_x9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ofcnx_x9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:file-blank" {...props}></Icon>
