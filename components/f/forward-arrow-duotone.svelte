<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s3e6fzopx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary s3e6fzopx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:forward-arrow-duotone" {...props}></Icon>
