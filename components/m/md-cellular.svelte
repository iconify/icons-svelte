<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qys4dgmlb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qys4dgmlb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-cellular" {...props}></Icon>
