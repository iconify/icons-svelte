<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tsx0ls6vz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="tsx0ls6vz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:expand-left-and-right" {...props}></Icon>
