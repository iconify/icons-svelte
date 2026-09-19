<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ojwzr62gf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ojwzr62gf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:bad-one" {...props}></Icon>
