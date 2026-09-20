<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l_v7-qb4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l_v7-qb4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:dv-filled" {...props}></Icon>
