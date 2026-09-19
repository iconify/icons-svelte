<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rs8zk6bka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rs8zk6bka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:github" {...props}></Icon>
