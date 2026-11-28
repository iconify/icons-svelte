<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q2121-bld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q2121-bld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:radio-tower-solid" {...props}></Icon>
