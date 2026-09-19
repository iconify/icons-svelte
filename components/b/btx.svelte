<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_fvy-bvc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="w_fvy-bvc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:btx" {...props}></Icon>
