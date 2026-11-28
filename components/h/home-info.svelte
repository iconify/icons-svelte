<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/thk8cdcdd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="thk8cdcdd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:home-info" {...props}></Icon>
