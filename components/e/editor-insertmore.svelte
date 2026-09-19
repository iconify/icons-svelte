<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ik_atsbov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ik_atsbov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:editor-insertmore" {...props}></Icon>
