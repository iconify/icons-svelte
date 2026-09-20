<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yx_qj-bhv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yx_qj-bhv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:align-item-left-fill" {...props}></Icon>
