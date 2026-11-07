<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zd1ch4bgm.css';
import '../../css/l/l_tzrhbkr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zd1ch4bgm"/><path class="l_tzrhbkr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:diagram-down-bold-duotone" {...props}></Icon>
