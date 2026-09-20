<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mm0hw1g4q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mm0hw1g4q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:circuit-cell" {...props}></Icon>
