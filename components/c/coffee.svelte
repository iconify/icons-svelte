<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rao5r5bls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="rao5r5bls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:coffee" {...props}></Icon>
