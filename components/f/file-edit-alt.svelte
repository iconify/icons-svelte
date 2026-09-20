<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/omfxs9b7j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="omfxs9b7j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:file-edit-alt" {...props}></Icon>
