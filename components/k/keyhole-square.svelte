<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rqbu23bhp.css';
import '../../css/n/ndzxj5bdh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rqbu23bhp"/><path class="ndzxj5bdh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:keyhole-square" {...props}></Icon>
