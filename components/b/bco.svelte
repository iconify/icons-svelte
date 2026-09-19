<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q8mz-kbyv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="q8mz-kbyv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:bco" {...props}></Icon>
