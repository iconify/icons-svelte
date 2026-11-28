<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tnk4p8vvq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tnk4p8vvq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:football-solid" {...props}></Icon>
