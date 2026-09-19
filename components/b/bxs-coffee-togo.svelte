<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ds-9jmb7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ds-9jmb7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-coffee-togo" {...props}></Icon>
