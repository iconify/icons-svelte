<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ts-x918ig.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ts-x918ig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:arrow-circle-down-solid" {...props}></Icon>
