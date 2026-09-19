<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/exqy2qb2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="exqy2qb2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:cable-car" {...props}></Icon>
