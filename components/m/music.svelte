<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lx56tqbsr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lx56tqbsr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:music" {...props}></Icon>
