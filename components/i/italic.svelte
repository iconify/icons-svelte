<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/flzd5qb8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="flzd5qb8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:italic" {...props}></Icon>
