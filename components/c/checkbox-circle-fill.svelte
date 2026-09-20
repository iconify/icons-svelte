<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s3rw4bb_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s3rw4bb_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:checkbox-circle-fill" {...props}></Icon>
