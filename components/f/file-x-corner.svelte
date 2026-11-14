<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gnei86bvr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gnei86bvr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:file-x-corner" {...props}></Icon>
