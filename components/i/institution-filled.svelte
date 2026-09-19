<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hhy12_s6e.css';
import '../../css/o/o_rxuaclz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hhy12_s6e"/><path class="o_rxuaclz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:institution-filled" {...props}></Icon>
