<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dlx4obcue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dlx4obcue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:compass-filled" {...props}></Icon>
