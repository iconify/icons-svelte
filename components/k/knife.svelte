<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/anheyy0qi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="anheyy0qi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:knife" {...props}></Icon>
