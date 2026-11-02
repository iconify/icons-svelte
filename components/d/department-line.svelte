<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mey0rqboh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mey0rqboh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:department-line" {...props}></Icon>
