<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nvob2xbyy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="nvob2xbyy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:beer" {...props}></Icon>
