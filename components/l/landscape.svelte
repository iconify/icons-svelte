<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xt3lcaczr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xt3lcaczr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:landscape" {...props}></Icon>
