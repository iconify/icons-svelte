<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pg4m9gbkq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="pg4m9gbkq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:global-nav-button" {...props}></Icon>
