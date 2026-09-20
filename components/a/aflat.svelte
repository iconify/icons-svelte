<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/twxj2puah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="twxj2puah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:aflat" {...props}></Icon>
