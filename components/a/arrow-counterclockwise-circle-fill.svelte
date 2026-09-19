<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uvgc2mbbg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="uvgc2mbbg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:arrow-counterclockwise-circle-fill" {...props}></Icon>
