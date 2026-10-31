<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zqto7nzoz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zqto7nzoz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:line-height-fill-round" {...props}></Icon>
