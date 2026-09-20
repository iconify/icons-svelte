<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/idyqitxti.css';
import '../../css/r/rarxg-bxy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="idyqitxti"/><path class="rarxg-bxy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:hospital-1-filled" {...props}></Icon>
