<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d7p86sb4n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d7p86sb4n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:file-solid" {...props}></Icon>
