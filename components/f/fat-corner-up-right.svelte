<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o0t4ebqbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o0t4ebqbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:fat-corner-up-right" {...props}></Icon>
