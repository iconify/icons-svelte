<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/txvtwob9t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="txvtwob9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:avatar" {...props}></Icon>
