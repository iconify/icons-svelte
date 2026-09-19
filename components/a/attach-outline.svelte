<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tztjsz4qt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tztjsz4qt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:attach-outline" {...props}></Icon>
