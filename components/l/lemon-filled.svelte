<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/noxt3rbhn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="noxt3rbhn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:lemon-filled" {...props}></Icon>
