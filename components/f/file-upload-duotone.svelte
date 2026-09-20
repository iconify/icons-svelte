<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dvqvjzb3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dvqvjzb3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:file-upload-duotone" {...props}></Icon>
