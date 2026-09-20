<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/exsgpsb5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="exsgpsb5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:docassemble-dark" {...props}></Icon>
