<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/enis4sb4v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="enis4sb4v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:imdb-dark" {...props}></Icon>
