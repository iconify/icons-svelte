<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zo0zz1btx.css';
import '../../css/o/o7lpvfbsc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="zo0zz1btx"/><path class="o7lpvfbsc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:latin-cross" {...props}></Icon>
