<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xs4ejwyhj.css';
import '../../css/f/fa6uf3bbr.css';
import '../../css/h/haqwlo80j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="xs4ejwyhj"/><path class="fa6uf3bbr"/><path class="haqwlo80j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:jquery" {...props}></Icon>
