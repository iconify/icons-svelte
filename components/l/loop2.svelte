<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u3n1iwbud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="u3n1iwbud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:loop2" {...props}></Icon>
