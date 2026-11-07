<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s2urmqbds.css';
import '../../css/e/ezj2uyggj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s2urmqbds"/><path class="ezj2uyggj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:laptop-2-bold" {...props}></Icon>
