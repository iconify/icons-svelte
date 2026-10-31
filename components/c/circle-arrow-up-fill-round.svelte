<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p656s3qqu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p656s3qqu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:circle-arrow-up-fill-round" {...props}></Icon>
