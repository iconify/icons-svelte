<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ar049kb4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ar049kb4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:logo-npm" {...props}></Icon>
