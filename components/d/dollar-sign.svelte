<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ncf43d60x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ncf43d60x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:dollar-sign" {...props}></Icon>
