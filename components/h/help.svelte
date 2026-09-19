<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pp9zd4bzg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="pp9zd4bzg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:help" {...props}></Icon>
