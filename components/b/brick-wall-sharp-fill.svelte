<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iyai-hbhy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iyai-hbhy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:brick-wall-sharp-fill" {...props}></Icon>
