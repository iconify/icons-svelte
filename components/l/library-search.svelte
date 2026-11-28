<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lor5nc46g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lor5nc46g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:library-search" {...props}></Icon>
