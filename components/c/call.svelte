<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ef5-nzb-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ef5-nzb-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:call" {...props}></Icon>
