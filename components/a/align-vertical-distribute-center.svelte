<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xzkxdebtu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xzkxdebtu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:align-vertical-distribute-center" {...props}></Icon>
