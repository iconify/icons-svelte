<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s1pqns7dy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s1pqns7dy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:building-gloss" {...props}></Icon>
