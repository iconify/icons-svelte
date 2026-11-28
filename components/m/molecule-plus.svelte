<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f1l84_une.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f1l84_une"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:molecule-plus" {...props}></Icon>
