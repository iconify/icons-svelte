<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b__nckb7f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="b__nckb7f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:airplane-takeoff" {...props}></Icon>
