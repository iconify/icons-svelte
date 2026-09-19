<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nhizzz3fb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="nhizzz3fb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:ksm" {...props}></Icon>
