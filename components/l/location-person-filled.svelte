<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/njyy8qbmd.css';
import '../../css/f/f-ksdqydc.css';
import '../../css/k/k6t4853ju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="njyy8qbmd"/><circle class="f-ksdqydc"/><path class="k6t4853ju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:location-person-filled" {...props}></Icon>
