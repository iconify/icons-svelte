<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c9ifqu2ej.css';
import '../../css/r/r-45tw1ar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c9ifqu2ej"/><path class="r-45tw1ar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:archive" {...props}></Icon>
