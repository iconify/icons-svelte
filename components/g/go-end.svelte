<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w833t_opg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="w833t_opg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:go-end" {...props}></Icon>
