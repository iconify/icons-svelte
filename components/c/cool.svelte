<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zj3ebeb9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="zj3ebeb9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:cool" {...props}></Icon>
