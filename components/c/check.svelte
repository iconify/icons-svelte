<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tp1qsbb8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tp1qsbb8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:check" {...props}></Icon>
