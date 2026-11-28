<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wbue_0b9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wbue_0b9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:mail-alert-solid" {...props}></Icon>
