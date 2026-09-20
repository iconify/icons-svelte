<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e2s3x9bme.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e2s3x9bme"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:list-arrow-down-bold" {...props}></Icon>
