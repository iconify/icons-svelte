<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cd_fl2b4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cd_fl2b4c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:printer-off-solid" {...props}></Icon>
