<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z6q_o_wdw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z6q_o_wdw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:aas-project-empty" {...props}></Icon>
