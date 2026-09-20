<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fo6qm9z4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fo6qm9z4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:module-puzzle-2-bold" {...props}></Icon>
