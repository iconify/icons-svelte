<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kdyoa5b9x.css';
import '../../css/o/oy550fbqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kdyoa5b9x"/><path class="oy550fbqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:notes-checklist-flip-bold" {...props}></Icon>
