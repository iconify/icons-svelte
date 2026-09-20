<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h29s4bc8i.css';
import '../../css/m/mb5862dny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h29s4bc8i"/><path class="mb5862dny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:file-attachment-filled" {...props}></Icon>
