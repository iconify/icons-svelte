<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i8zaambxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i8zaambxw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:neo4j-dark" {...props}></Icon>
