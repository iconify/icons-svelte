<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lzow25bmr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lzow25bmr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:flash-alert-outline" {...props}></Icon>
