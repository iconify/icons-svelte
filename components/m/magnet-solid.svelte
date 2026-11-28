<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/grs1shbxi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="grs1shbxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:magnet-solid" {...props}></Icon>
