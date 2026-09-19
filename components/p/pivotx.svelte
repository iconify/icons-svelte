<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/irzz9_mlb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":960,"height":1024};
const content = `<path class="irzz9_mlb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:pivotx" {...props}></Icon>
