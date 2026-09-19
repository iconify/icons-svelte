<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vlvo0thnk.css';
import '../../css/i/iih3otspu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vlvo0thnk"/><path class="iih3otspu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-watson-machine-learning" {...props}></Icon>
