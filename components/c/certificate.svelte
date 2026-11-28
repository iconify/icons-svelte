<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mmlxqf6mo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mmlxqf6mo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:certificate" {...props}></Icon>
