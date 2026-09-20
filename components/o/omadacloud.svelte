<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lv7jl220f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lv7jl220f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:omadacloud" {...props}></Icon>
