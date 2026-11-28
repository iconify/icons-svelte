<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nhu_33egn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nhu_33egn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:rewind" {...props}></Icon>
