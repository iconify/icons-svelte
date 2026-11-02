<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-x9pmb4n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k-x9pmb4n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:midi-line" {...props}></Icon>
