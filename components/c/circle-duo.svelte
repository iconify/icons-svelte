<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mp_1auk9l.css';
import '../../css/c/cuj9p20cj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mp_1auk9l secondary"/><path class="cuj9p20cj primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:circle-duo" {...props}></Icon>
