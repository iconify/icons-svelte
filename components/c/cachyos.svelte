<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q_hnlpuwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="q_hnlpuwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:cachyos" {...props}></Icon>
