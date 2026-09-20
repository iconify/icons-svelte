<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hmld1dbat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hmld1dbat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:city-9-filled" {...props}></Icon>
