<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v_zmtc4ke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="v_zmtc4ke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:moon" {...props}></Icon>
