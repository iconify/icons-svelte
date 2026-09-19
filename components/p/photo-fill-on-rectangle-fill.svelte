<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g4jxjzb6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="g4jxjzb6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:photo-fill-on-rectangle-fill" {...props}></Icon>
