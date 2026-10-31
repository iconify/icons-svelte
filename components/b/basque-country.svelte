<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u_4c0abso.css';
import '../../css/h/hni6s_bol.css';
import '../../css/y/yjdgsrw6x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="u_4c0abso"/><path class="hni6s_bol"/><path class="yjdgsrw6x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:basque-country" {...props}></Icon>
