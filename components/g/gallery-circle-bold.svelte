<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h-3wh2bpf.css';
import '../../css/r/rxs5fmtky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h-3wh2bpf"/><path clip-rule="evenodd" class="rxs5fmtky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:gallery-circle-bold" {...props}></Icon>
