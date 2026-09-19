<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pw8j__w4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1792};
const content = `<path class="pw8j__w4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:n-square" {...props}></Icon>
