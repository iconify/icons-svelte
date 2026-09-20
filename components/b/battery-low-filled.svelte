<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w7ce1ju2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w7ce1ju2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:battery-low-filled" {...props}></Icon>
