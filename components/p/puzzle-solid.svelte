<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u65bls48j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u65bls48j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:puzzle-solid" {...props}></Icon>
