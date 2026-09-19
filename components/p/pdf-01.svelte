<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g3k6s3b4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g3k6s3b4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:pdf-01" {...props}></Icon>
