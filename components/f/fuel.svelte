<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bnwo09bcb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bnwo09bcb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:fuel" {...props}></Icon>
