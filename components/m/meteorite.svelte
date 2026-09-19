<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k4m6t8bnp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="k4m6t8bnp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:meteorite" {...props}></Icon>
