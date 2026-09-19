<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xfjy_dbux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xfjy_dbux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-refresh-circle" {...props}></Icon>
