<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g7t93nb3i.css';
import '../../css/q/qu8iegbod.css';
import '../../css/g/g7-s2nbhk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="g7t93nb3i"/><path class="qu8iegbod"/><path class="g7-s2nbhk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:bahamas" {...props}></Icon>
