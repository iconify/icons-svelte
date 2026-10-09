<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/op02w5bbu.css';
import '../../css/s/s6hyw202b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="op02w5bbu"/><path class="s6hyw202b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:redo-20" {...props}></Icon>
