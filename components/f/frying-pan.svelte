<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nbh0m6b5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nbh0m6b5f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:frying-pan" {...props}></Icon>
