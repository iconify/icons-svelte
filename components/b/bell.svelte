<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d7sk8owmb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="d7sk8owmb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:bell" {...props}></Icon>
