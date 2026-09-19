<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u5lighxht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="u5lighxht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:people-speak" {...props}></Icon>
