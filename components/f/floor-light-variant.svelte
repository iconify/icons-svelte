<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z5-n9-bgf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z5-n9-bgf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:floor-light-variant" {...props}></Icon>
