<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j712kcbjb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="j712kcbjb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:diamond-one" {...props}></Icon>
