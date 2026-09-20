<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/adw19fflm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="adw19fflm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:incoming-call" {...props}></Icon>
