<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zt8ittjqb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zt8ittjqb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:fast-arrow-right" {...props}></Icon>
