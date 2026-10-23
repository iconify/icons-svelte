<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/as5fqu2ht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="as5fqu2ht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:file-play" {...props}></Icon>
