<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fkq5-0cbt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":770};
const content = `<path class="fkq5-0cbt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:panoramaalt" {...props}></Icon>
