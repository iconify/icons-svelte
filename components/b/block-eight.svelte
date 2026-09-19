<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fct2vly4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fct2vly4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:block-eight" {...props}></Icon>
