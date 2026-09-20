<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yx3dfzuvk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yx3dfzuvk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:play-box-edit-outline" {...props}></Icon>
