<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h8w0ypeiq.css';
import '../../css/n/nox4hglku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h8w0ypeiq"/><path class="nox4hglku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:chevron-right" {...props}></Icon>
