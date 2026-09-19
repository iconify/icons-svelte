<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e8m74qb9x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e8m74qb9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:coin-stack" {...props}></Icon>
