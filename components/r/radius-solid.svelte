<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tg1i90eaw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tg1i90eaw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:radius-solid" {...props}></Icon>
