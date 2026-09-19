<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nil35lbrw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":543,"height":768};
const content = `<path class="nil35lbrw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:ink" {...props}></Icon>
