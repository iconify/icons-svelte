<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yqgaffhxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yqgaffhxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:layer-arrow-down-solid" {...props}></Icon>
