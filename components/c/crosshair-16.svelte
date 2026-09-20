<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/coc607b1m.css';
import '../../css/d/d0kk4rblb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="coc607b1m"/><path clip-rule="evenodd" class="d0kk4rblb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:crosshair-16" {...props}></Icon>
