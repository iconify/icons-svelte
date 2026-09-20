<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lks-hgj9k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lks-hgj9k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:rewind-diamond-solid" {...props}></Icon>
