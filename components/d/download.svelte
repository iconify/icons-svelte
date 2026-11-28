<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lvkd-1bzm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lvkd-1bzm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:download" {...props}></Icon>
