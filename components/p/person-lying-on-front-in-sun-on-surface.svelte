<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rsm-84idg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="rsm-84idg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-lying-on-front-in-sun-on-surface" {...props}></Icon>
