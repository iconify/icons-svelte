<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s3kg0ka3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s3kg0ka3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:gavel-filled" {...props}></Icon>
