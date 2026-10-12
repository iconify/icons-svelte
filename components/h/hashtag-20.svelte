<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/acea_pbcj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="acea_pbcj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:hashtag-20" {...props}></Icon>
