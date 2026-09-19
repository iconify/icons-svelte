<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i9l3vac1v.css';
import '../../css/x/x8lyhp39e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="i9l3vac1v"/><path class="x8lyhp39e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:cz" {...props}></Icon>
