<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nt6lf-77j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nt6lf-77j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:bookmark" {...props}></Icon>
