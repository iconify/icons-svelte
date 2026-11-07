<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wnjvphbgm.css';
import '../../css/t/twgj61vyf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wnjvphbgm"/><path class="twgj61vyf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:call-dropped-rounded-bold" {...props}></Icon>
