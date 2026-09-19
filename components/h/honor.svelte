<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dou5g5byt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dou5g5byt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:honor" {...props}></Icon>
