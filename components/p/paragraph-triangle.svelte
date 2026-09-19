<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ulk470blc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ulk470blc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:paragraph-triangle" {...props}></Icon>
