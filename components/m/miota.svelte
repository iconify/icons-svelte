<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w772vtf7n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="w772vtf7n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:miota" {...props}></Icon>
