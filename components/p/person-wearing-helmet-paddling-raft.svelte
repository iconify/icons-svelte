<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/crev81m-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="crev81m-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-wearing-helmet-paddling-raft" {...props}></Icon>
