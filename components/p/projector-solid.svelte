<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t83fg4byq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t83fg4byq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:projector-solid" {...props}></Icon>
