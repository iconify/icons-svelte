<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mhch_fo3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mhch_fo3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:database" {...props}></Icon>
