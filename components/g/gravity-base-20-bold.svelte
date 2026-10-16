<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v88ye4bop.css';
import '../../css/r/r8ygzbbjv.css';
import '../../css/y/yfoxxnbix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="v88ye4bop"/><path class="r8ygzbbjv"/><path class="yfoxxnbix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:gravity-base-20-bold" {...props}></Icon>
