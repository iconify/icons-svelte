<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vhl3z13hj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="vhl3z13hj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:mark-down-language" {...props}></Icon>
