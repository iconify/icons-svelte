<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r8p_jx3oe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r8p_jx3oe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:locker-solid" {...props}></Icon>
