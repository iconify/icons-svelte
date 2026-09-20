<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vgw1xabjo.css';
import '../../css/a/ag6jefblo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vgw1xabjo"/><path class="ag6jefblo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:money-filled" {...props}></Icon>
