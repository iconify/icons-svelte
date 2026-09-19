<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/diqq20_5b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="diqq20_5b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:habr" {...props}></Icon>
