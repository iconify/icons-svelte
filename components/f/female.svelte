<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gx5brxb6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gx5brxb6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:female" {...props}></Icon>
