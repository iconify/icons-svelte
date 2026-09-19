<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b3tx3lj_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="b3tx3lj_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:comb" {...props}></Icon>
