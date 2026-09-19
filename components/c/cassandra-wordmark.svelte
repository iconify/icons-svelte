<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m52mwjdue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="m52mwjdue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:cassandra-wordmark" {...props}></Icon>
