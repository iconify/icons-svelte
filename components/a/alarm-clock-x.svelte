<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xkk5hqbwn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xkk5hqbwn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:alarm-clock-x" {...props}></Icon>
