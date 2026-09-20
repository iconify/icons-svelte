<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yua8bcbyc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yua8bcbyc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:clock-three-solid" {...props}></Icon>
