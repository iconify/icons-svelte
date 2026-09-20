<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ntt91gjof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ntt91gjof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:paintbrush-24" {...props}></Icon>
