<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ysdpklb7y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ysdpklb7y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:grs" {...props}></Icon>
