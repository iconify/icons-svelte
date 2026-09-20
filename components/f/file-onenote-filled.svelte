<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hz3kvt0ck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hz3kvt0ck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:file-onenote-filled" {...props}></Icon>
