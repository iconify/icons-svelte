<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lub6lcczs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lub6lcczs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:flag-x" {...props}></Icon>
