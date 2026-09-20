<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bugl1cbsm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bugl1cbsm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:live-line" {...props}></Icon>
