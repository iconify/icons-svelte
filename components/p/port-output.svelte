<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pp_wowb2j.css';
import '../../css/l/lt2mkcbkk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pp_wowb2j"/><path class="lt2mkcbkk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:port-output" {...props}></Icon>
