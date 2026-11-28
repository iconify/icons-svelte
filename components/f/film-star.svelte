<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c8za1ccgc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c8za1ccgc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:film-star" {...props}></Icon>
