<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ztdu4abng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ztdu4abng"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:logo-tdesign" {...props}></Icon>
