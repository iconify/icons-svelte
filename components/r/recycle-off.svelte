<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cw3qqeyqu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cw3qqeyqu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:recycle-off" {...props}></Icon>
