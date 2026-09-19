<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qubcu_soi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qubcu_soi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:dock-bottom-right" {...props}></Icon>
