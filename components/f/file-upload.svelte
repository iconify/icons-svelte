<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/idkx_pblf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="idkx_pblf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:file-upload" {...props}></Icon>
