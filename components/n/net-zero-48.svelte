<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hac57wbhi.css';
import '../../css/x/x7aj4qb4r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hac57wbhi"/><path class="x7aj4qb4r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:net-zero-48" {...props}></Icon>
