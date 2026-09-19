<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/plqeeh25x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="plqeeh25x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-browsers" {...props}></Icon>
