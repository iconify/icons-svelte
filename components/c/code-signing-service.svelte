<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xo26xfwgu.css';
import '../../css/r/rokywmbwd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<circle class="xo26xfwgu"/><path class="rokywmbwd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:code-signing-service" {...props}></Icon>
