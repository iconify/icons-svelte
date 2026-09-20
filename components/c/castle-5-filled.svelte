<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-9vmjg_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g-9vmjg_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:castle-5-filled" {...props}></Icon>
