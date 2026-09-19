<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d3ibzzb5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="d3ibzzb5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:cplusplus" {...props}></Icon>
