<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qgh_1byzg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qgh_1byzg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:road" {...props}></Icon>
