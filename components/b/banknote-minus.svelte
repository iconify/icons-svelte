<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jf_g46bxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jf_g46bxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:banknote-minus" {...props}></Icon>
