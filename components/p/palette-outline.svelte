<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ybmo5mmpv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ybmo5mmpv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:palette-outline" {...props}></Icon>
