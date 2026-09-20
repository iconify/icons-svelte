<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tnghrpb1d.css';
import '../../css/b/by4txvb2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tnghrpb1d"/><path class="by4txvb2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:clock-nine" {...props}></Icon>
