<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u8ix8qb8j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u8ix8qb8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:lock-x" {...props}></Icon>
