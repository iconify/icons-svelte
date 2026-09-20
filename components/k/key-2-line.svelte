<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/juqc6xgep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="juqc6xgep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:key-2-line" {...props}></Icon>
