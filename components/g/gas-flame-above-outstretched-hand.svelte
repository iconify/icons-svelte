<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vjnsghb1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="vjnsghb1l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:gas-flame-above-outstretched-hand" {...props}></Icon>
