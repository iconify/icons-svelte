<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mmrsxwynv.css';
import '../../css/h/h4au9l6mg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mmrsxwynv"/><path class="h4au9l6mg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:camera-outline" {...props}></Icon>
