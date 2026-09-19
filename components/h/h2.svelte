<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ls3gd3b9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ls3gd3b9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:h2" {...props}></Icon>
