<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ofpbh-bef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ofpbh-bef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:barbell-solid" {...props}></Icon>
