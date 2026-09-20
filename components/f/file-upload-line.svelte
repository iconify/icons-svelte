<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jdhhtkvfv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jdhhtkvfv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:file-upload-line" {...props}></Icon>
