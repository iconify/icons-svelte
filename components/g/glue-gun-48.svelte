<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ycd8zvvjv.css';
import '../../css/c/c9il3frxy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ycd8zvvjv"/><path class="c9il3frxy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:glue-gun-48" {...props}></Icon>
