<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bk-qwvomb.css';
import '../../css/j/jfe6ttbpf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bk-qwvomb"/><path class="jfe6ttbpf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:penn-state-nittany-lions" {...props}></Icon>
