<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u506o2_2r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u506o2_2r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:headphones-light" {...props}></Icon>
