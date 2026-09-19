<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-q-q20kk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":642,"height":1024};
const content = `<path class="k-q-q20kk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:cursor" {...props}></Icon>
