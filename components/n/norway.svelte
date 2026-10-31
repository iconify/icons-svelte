<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rqe71b-9z.css';
import '../../css/l/l1kbw1b1l.css';
import '../../css/c/cfoaekbqc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="rqe71b-9z"/><path class="l1kbw1b1l"/><path class="cfoaekbqc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:norway" {...props}></Icon>
