<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yx1zgacyc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yx1zgacyc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:light-bulb-filled" {...props}></Icon>
