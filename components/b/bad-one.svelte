<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xick6v_8g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xick6v_8g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:bad-one" {...props}></Icon>
