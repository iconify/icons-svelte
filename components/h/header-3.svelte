<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/scuur4oxh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="scuur4oxh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:header-3" {...props}></Icon>
