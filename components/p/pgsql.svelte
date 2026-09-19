<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u2cez91zb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="u2cez91zb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:pgsql" {...props}></Icon>
