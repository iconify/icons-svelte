<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ne-jowj6i.css';
import '../../css/t/ty8mqjb4w.css';
import '../../css/p/p-x0sqbzb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ne-jowj6i"/><path class="ty8mqjb4w"/><path class="p-x0sqbzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:liquid-hydrogen-48-bold" {...props}></Icon>
