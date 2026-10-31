<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yr3_-mb_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yr3_-mb_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:circle-medium-fill-round" {...props}></Icon>
