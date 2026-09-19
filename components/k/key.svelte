<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cnqn2zbni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="cnqn2zbni"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:key" {...props}></Icon>
