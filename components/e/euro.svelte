<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qec68vzfg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qec68vzfg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:euro" {...props}></Icon>
