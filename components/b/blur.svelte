<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fiugobc0l.css';
import '../../css/b/bc69m5bpz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fiugobc0l"/><path class="bc69m5bpz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:blur" {...props}></Icon>
