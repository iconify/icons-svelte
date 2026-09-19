<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g4e94nblv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g4e94nblv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-paper-plane" {...props}></Icon>
