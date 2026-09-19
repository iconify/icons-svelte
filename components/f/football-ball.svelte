<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g0mun5b4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g0mun5b4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:football-ball" {...props}></Icon>
