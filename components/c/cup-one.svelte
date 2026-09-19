<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-hb33v6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="c-hb33v6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:cup-one" {...props}></Icon>
