<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jb2s3pbyl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jb2s3pbyl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:dumbbell-small-outline" {...props}></Icon>
