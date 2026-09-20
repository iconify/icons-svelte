<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lglvlnxox.css';
import '../../css/k/ktnt72cco.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lglvlnxox"/><path class="ktnt72cco"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:coffee-espresso-machine-bold" {...props}></Icon>
