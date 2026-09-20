<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ze611lb2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ze611lb2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:armchair2" {...props}></Icon>
