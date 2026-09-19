<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n_lnmcbbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="n_lnmcbbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:phone" {...props}></Icon>
