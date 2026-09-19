<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o_dv1kbpf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o_dv1kbpf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:broom" {...props}></Icon>
