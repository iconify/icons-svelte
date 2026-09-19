<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bdvfihbpq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bdvfihbpq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:mode-dark-bold" {...props}></Icon>
