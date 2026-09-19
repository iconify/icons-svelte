<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bpfg_4bzq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bpfg_4bzq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:gaming" {...props}></Icon>
