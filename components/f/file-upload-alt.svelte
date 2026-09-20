<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f7md9u2zr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f7md9u2zr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:file-upload-alt" {...props}></Icon>
