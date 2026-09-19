<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g8n_clbvl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="g8n_clbvl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:branch-one" {...props}></Icon>
