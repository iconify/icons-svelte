<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hlcpntlei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hlcpntlei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:ella" {...props}></Icon>
