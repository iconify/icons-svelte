<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/roqffxsut.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="roqffxsut"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:circle-dotted" {...props}></Icon>
