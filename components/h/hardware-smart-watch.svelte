<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pdvnelb_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pdvnelb_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:hardware-smart-watch" {...props}></Icon>
