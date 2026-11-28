<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xbo-ubbap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xbo-ubbap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:hammer-solid" {...props}></Icon>
