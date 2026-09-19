<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mbd6hocoo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mbd6hocoo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:box" {...props}></Icon>
