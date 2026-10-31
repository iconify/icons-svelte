<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x90kqacjo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x90kqacjo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:numbers" {...props}></Icon>
