<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z4ra9hb5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z4ra9hb5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:heart-minus-solid" {...props}></Icon>
