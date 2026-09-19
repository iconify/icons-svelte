<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b5nslhbez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="b5nslhbez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:cirrusci" {...props}></Icon>
