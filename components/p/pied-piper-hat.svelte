<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xikwt1jtn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="xikwt1jtn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:pied-piper-hat" {...props}></Icon>
