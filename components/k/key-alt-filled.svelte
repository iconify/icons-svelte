<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tpf00ybcb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tpf00ybcb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:key-alt-filled" {...props}></Icon>
