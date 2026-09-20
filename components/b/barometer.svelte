<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o6mhir3ft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="o6mhir3ft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:barometer" {...props}></Icon>
