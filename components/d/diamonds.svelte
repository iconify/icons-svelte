<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cw0m6zb1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cw0m6zb1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:diamonds" {...props}></Icon>
