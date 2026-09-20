<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jea-rybql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jea-rybql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:cloud" {...props}></Icon>
