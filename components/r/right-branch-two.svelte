<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/glgjn_3wv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="glgjn_3wv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:right-branch-two" {...props}></Icon>
