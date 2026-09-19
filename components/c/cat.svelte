<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wr58843mv.css';
import '../../css/c/c9r1x5bpq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wr58843mv"/><path class="c9r1x5bpq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:cat" {...props}></Icon>
