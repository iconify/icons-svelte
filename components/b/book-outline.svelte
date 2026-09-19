<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sii5elbef.css';
import '../../css/v/vdb-37byt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sii5elbef"/><path clip-rule="evenodd" class="vdb-37byt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:book-outline" {...props}></Icon>
