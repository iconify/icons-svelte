<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b70_0tbpv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b70_0tbpv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:post-it-note-remove" {...props}></Icon>
