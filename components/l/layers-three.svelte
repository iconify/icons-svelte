<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_ybmzbvs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i_ybmzbvs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:layers-three" {...props}></Icon>
