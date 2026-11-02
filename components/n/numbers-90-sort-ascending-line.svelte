<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o4qcw2v3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o4qcw2v3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:numbers-90-sort-ascending-line" {...props}></Icon>
