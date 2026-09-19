<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nvpejw8_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="nvpejw8_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:list-numbers" {...props}></Icon>
