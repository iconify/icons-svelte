<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v_l0zgbxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="v_l0zgbxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:pull-right" {...props}></Icon>
