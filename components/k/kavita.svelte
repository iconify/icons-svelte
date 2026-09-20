<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c___7e6_j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c___7e6_j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:kavita" {...props}></Icon>
