<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j9beefbwk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="j9beefbwk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:deployment-unit-technical-presentation" {...props}></Icon>
