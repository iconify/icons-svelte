<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rw-97iyer.css';
import '../../css/a/az4h9ufdp.css';
import '../../css/p/pc91ydrlr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="rw-97iyer"/><path class="az4h9ufdp"/><path class="pc91ydrlr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:botswana" {...props}></Icon>
