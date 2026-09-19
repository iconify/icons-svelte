<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eo6mkubnv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="eo6mkubnv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:knc" {...props}></Icon>
