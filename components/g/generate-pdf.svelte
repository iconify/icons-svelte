<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hvhy-ba_m.css';
import '../../css/n/n7pqid28s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hvhy-ba_m"/><path class="n7pqid28s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:generate-pdf" {...props}></Icon>
