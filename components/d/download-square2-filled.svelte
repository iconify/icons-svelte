<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lv7pwtboh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lv7pwtboh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:download-square2-filled" {...props}></Icon>
