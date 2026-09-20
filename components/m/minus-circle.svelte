<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sn0ft0bop.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sn0ft0bop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:minus-circle" {...props}></Icon>
