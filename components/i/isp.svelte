<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yjfe0fb-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yjfe0fb-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:isp" {...props}></Icon>
