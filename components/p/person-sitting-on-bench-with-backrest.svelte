<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/do9d8sb7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="do9d8sb7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-sitting-on-bench-with-backrest" {...props}></Icon>
