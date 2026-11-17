<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jm6z8kb8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jm6z8kb8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:levoit-air-purifier" {...props}></Icon>
