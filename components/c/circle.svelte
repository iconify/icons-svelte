<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hre7pb13f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hre7pb13f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:circle" {...props}></Icon>
