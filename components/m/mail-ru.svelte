<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t1brok5-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="t1brok5-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:mail-ru" {...props}></Icon>
