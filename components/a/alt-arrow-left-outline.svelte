<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s3t23s65d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s3t23s65d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:alt-arrow-left-outline" {...props}></Icon>
