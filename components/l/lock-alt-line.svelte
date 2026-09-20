<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3j-qp_1n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l3j-qp_1n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:lock-alt-line" {...props}></Icon>
