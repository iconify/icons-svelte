<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p47rngo5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p47rngo5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:globus" {...props}></Icon>
