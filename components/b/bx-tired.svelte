<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fmu3bk6pi.css';
import '../../css/w/wqbkv8u2i.css';
import '../../css/k/k31e-btyh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fmu3bk6pi"/><path class="wqbkv8u2i"/><path class="k31e-btyh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-tired" {...props}></Icon>
