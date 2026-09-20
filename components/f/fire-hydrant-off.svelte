<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nkjt2n3sd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nkjt2n3sd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:fire-hydrant-off" {...props}></Icon>
