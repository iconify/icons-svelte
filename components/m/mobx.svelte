<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y2zh8jldm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y2zh8jldm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:mobx" {...props}></Icon>
